<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kumcrmbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kumcrmbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-boarding-monorail-transit-vehicle-with-destination-display" /></template>
