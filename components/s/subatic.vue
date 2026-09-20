<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7okh1bgg.css';
import '../../css/g/gakqf2bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p7okh1bgg"/><path class="gakqf2bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:subatic" /></template>
