<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r21m_6bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r21m_6bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-star-filled" /></template>
