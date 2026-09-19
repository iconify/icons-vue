<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwlarub2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="gwlarub2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:open-padlock" /></template>
