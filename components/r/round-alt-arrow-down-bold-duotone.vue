<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghfixm1dc.css';
import '../../css/j/jq-gf3byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghfixm1dc"/><path class="jq-gf3byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-alt-arrow-down-bold-duotone" /></template>
