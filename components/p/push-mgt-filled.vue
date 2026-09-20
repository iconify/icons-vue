<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdf1hubnu.css';
import '../../css/f/f69nz6bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kdf1hubnu"/><path clip-rule="evenodd" class="f69nz6bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:push-mgt-filled" /></template>
