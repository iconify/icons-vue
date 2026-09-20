<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks94omb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks94omb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:save" /></template>
