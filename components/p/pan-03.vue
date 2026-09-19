<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/plbf5dbsw.css';
import '../../css/z/z7dwaybhf.css';
import '../../css/y/yhipwkb9a.css';
import '../../css/w/wu2k7qbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="plbf5dbsw"/><path class="z7dwaybhf"/><path class="yhipwkb9a"/><path class="wu2k7qbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pan-03" /></template>
