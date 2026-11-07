<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixky28b1f.css';
import '../../css/y/ye90rbccq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixky28b1f"/><path class="ye90rbccq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pip-2-bold-duotone" /></template>
