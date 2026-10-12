<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0ips-hnl.css';
import '../../css/f/f2vy__bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l0ips-hnl"/><path class="f2vy__bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:trash-off-filled" /></template>
