<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htbowudik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="htbowudik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:user-new-filled" /></template>
