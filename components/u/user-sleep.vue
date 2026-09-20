<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj4d1uf6r.css';
import '../../css/i/iscnj5bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qj4d1uf6r"/><path class="iscnj5bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:user-sleep" /></template>
