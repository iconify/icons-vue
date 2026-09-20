<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqpcls_me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jqpcls_me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:pad-filled" /></template>
