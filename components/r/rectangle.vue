<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adn-au1cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adn-au1cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:rectangle" /></template>
