<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r48w19b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r48w19b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-boarding-tram-with-destination-display-and-pantograph-on-tram-track" /></template>
