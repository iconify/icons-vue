<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp78ehb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yp78ehb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:skateboard" /></template>
