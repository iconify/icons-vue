<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovcv3qbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovcv3qbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:stethoscope-filled" /></template>
