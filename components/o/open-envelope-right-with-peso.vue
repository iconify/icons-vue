<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnxu-lb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bnxu-lb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:open-envelope-right-with-peso" /></template>
