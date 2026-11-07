<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6j569bdk.css';
import '../../css/l/l9hde_zgu.css';
import '../../css/b/bvzc07axr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6j569bdk"/><path class="l9hde_zgu"/><path class="bvzc07axr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:routing-bold-duotone" /></template>
