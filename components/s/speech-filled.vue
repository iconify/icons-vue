<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqlsd2b2r.css';
import '../../css/a/aepwucb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqlsd2b2r"/><path class="aepwucb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:speech-filled" /></template>
