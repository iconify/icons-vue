<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pla5l_p9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pla5l_p9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:upload-filled" /></template>
