<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp_r4gbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rp_r4gbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sort-filled" /></template>
