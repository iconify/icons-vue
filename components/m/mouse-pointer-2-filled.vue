<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc4hsghsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc4hsghsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouse-pointer-2-filled" /></template>
