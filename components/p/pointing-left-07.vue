<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9uds8nda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9uds8nda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pointing-left-07" /></template>
