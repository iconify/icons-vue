<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmhbl_bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmhbl_bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:thermostat-solid" /></template>
