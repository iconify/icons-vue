<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sddj92-ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sddj92-ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:video-fill" /></template>
