<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2p_l-b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b2p_l-b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:service-fill" /></template>
