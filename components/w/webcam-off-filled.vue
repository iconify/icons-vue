<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv_363bea.css';
import '../../css/t/t6xotcc8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fv_363bea"/><path class="t6xotcc8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:webcam-off-filled" /></template>
