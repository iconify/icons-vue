<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvw8s9b2p.css';
import '../../css/q/qq2gd69ng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yvw8s9b2p"/><path class="qq2gd69ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:milk-off-filled" /></template>
