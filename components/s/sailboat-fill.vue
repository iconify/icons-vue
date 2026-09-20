<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7zrzpbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7zrzpbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sailboat-fill" /></template>
