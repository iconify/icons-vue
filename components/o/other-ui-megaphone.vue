<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aihw0sbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aihw0sbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-megaphone" /></template>
