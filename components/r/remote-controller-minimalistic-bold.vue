<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdbfs0bsu.css';
import '../../css/r/riimeibow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdbfs0bsu"/><path clip-rule="evenodd" class="riimeibow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:remote-controller-minimalistic-bold" /></template>
