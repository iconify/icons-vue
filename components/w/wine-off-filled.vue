<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi3b2p9eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi3b2p9eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:wine-off-filled" /></template>
