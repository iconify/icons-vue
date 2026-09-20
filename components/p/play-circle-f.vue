<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7g2p8hrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="p7g2p8hrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:play-circle-f" /></template>
