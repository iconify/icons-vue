<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb93m_k3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb93m_k3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:threads" /></template>
