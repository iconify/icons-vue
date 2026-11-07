<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st24108fl.css';
import '../../css/g/gn6fo9ori.css';
import '../../css/p/pqifm1b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st24108fl"/><path class="gn6fo9ori"/><path class="pqifm1b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:posts-carousel-horizontal-bold" /></template>
