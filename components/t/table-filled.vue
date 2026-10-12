<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2tz9zcxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2tz9zcxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:table-filled" /></template>
