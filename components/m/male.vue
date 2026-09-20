<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuh6h7j6z.css';
import '../../css/x/xfomdp99f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="vuh6h7j6z"/><circle class="xfomdp99f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:male" /></template>
