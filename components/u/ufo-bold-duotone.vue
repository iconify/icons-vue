<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgv6vob-r.css';
import '../../css/d/dr-zygb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgv6vob-r"/><path class="dr-zygb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ufo-bold-duotone" /></template>
