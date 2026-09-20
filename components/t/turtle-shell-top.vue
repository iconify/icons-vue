<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1sy9hifo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s1sy9hifo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:turtle-shell-top" /></template>
