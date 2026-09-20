<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvfqb6dsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qvfqb6dsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-boarding-transit-vehicle-with-destination-display-and-pantograph-on-tram-track" /></template>
