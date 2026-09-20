<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj67-cbkl.css';
import '../../css/g/gpayj6yuu.css';
import '../../css/o/odhhf9bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj67-cbkl"/><path class="gpayj6yuu"/><path class="odhhf9bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:reddit" /></template>
