<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxq908p6m.css';
import '../../css/m/mdkytublt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxq908p6m"/><path class="mdkytublt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:traffic-cone-filled" /></template>
