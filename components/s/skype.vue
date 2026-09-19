<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzfdp0cri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nzfdp0cri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:skype" /></template>
