<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br3iyqaeh.css';
import '../../css/g/gng30g8lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="br3iyqaeh"/><path class="gng30g8lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-users" /></template>
