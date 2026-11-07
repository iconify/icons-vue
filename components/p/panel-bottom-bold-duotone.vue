<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9asq1fvt.css';
import '../../css/l/l4t7dwu3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9asq1fvt"/><path class="l4t7dwu3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-bottom-bold-duotone" /></template>
