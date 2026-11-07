<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iln029b4a.css';
import '../../css/t/twczvmatf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iln029b4a"/><path class="twczvmatf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panorama-bold-duotone" /></template>
