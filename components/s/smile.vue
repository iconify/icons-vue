<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqxcp5bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="zqxcp5bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:smile" /></template>
