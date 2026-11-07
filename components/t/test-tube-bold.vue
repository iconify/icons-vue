<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xre4jslvu.css';
import '../../css/w/wq4oxm77o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xre4jslvu"/><path class="wq4oxm77o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:test-tube-bold" /></template>
