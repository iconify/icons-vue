<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur7kpoblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur7kpoblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tag-filled" /></template>
