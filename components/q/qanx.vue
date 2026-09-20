<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgb8wkb_n.css';
import '../../css/v/vpvf7rb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgb8wkb_n"/><path class="vpvf7rb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:qanx" /></template>
