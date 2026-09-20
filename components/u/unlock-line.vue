<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw54qac6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw54qac6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:unlock-line" /></template>
