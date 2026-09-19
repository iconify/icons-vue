<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkoonwrcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bkoonwrcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-3-fill" /></template>
