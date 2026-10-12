<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3r4dhb5z.css';
import '../../css/l/l9jgh7bvz.css';
import '../../css/s/st45emjbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l3r4dhb5z"/><path class="l9jgh7bvz"/><path class="st45emjbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:users-plus-48-bold" /></template>
