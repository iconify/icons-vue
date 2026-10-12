<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxe47ha6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxe47ha6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:replace-filled" /></template>
