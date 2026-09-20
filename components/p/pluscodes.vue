<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk1ad80py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk1ad80py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:pluscodes" /></template>
