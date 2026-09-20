<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz646ky1a.css';
import '../../css/a/aucdcts6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dz646ky1a"/><path class="aucdcts6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reaparr-light" /></template>
