<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awsea6blm.css';
import '../../css/e/e7rwfg02i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="awsea6blm"/><path class="e7rwfg02i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:offshore-substation-48-bold" /></template>
