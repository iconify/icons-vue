<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhcb065st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhcb065st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:sidebar-line-left" /></template>
