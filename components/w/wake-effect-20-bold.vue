<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6k8gux7d.css';
import '../../css/i/ilc61dbwx.css';
import '../../css/q/qdwklz3cm.css';
import '../../css/y/yhk6owtet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h6k8gux7d"/><path class="ilc61dbwx"/><path class="qdwklz3cm"/><path class="yhk6owtet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wake-effect-20-bold" /></template>
