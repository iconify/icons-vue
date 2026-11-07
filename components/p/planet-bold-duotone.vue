<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2m6oob6i.css';
import '../../css/k/kbnhcials.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2m6oob6i"/><path class="kbnhcials"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-bold-duotone" /></template>
