<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4_v15wno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4_v15wno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:turntable-outline" /></template>
