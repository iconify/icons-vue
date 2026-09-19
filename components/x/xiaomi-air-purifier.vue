<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m94q-dbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m94q-dbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:xiaomi-air-purifier" /></template>
