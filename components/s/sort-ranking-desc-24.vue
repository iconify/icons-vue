<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1ds-6sfp.css';
import '../../css/p/p_sp1no_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1ds-6sfp"/><path clip-rule="evenodd" class="p_sp1no_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sort-ranking-desc-24" /></template>
