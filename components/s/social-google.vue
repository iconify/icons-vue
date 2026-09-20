<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrml8r0nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zrml8r0nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:social-google" /></template>
