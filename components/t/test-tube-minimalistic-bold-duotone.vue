<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6iy-gb8w.css';
import '../../css/u/uif7prbix.css';
import '../../css/w/w3j8bvi0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6iy-gb8w"/><path class="uif7prbix"/><path class="w3j8bvi0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:test-tube-minimalistic-bold-duotone" /></template>
