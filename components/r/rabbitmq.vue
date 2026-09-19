<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfj4tjbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jfj4tjbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:rabbitmq" /></template>
