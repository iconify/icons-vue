<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjw3e_ued.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjw3e_ued"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:sparkles" /></template>
