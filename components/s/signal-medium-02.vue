<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6f32gbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6f32gbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:signal-medium-02" /></template>
