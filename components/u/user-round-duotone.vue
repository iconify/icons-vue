<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pthc7kbbw.css';
import '../../css/i/ig-kolbmk.css';
import '../../css/p/plk3fn3le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pthc7kbbw"/><path class="ig-kolbmk"/><path class="plk3fn3le"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-duotone" /></template>
