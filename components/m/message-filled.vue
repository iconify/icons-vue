<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c17cwxbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c17cwxbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:message-filled" /></template>
