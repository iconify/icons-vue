<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y66n86cjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y66n86cjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-id-filled" /></template>
