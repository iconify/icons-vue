<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge79lcctt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ge79lcctt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:unlock-filled" /></template>
