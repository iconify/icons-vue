<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-px0kjof.css';
import '../../css/p/p0hdxnbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-px0kjof"/><path class="p0hdxnbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:power-filled" /></template>
