<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocdgddc2f.css';
import '../../css/w/wk87j1b9c.css';
import '../../css/i/itu3zmsxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ocdgddc2f"/><path clip-rule="evenodd" class="wk87j1b9c"/><path class="itu3zmsxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:map-location-outline" /></template>
