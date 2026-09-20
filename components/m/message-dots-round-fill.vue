<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfrkmdbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfrkmdbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:message-dots-round-fill" /></template>
