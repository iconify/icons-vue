<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7z7vbbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7z7vbbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:netflix-alt2" /></template>
