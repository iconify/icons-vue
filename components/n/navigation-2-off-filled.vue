<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gscxrkdyg.css';
import '../../css/d/du48p_lje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gscxrkdyg"/><path clip-rule="evenodd" class="du48p_lje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:navigation-2-off-filled" /></template>
