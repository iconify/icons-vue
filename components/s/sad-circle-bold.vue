<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn3o-27jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nn3o-27jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sad-circle-bold" /></template>
