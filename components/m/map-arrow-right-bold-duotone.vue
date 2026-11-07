<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4zeb_b-f.css';
import '../../css/a/aihie_dzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4zeb_b-f"/><path class="aihie_dzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-right-bold-duotone" /></template>
