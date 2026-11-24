<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkvkheb0s.css';
import '../../css/c/cwsolebjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkvkheb0s"/><path class="cwsolebjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:smartphone-nfc-filled" /></template>
