<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iigzx5b6a.css';
import '../../css/o/ou4giibdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iigzx5b6a"/><path class="ou4giibdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:volume-2-filled" /></template>
