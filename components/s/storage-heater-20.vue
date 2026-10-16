<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9kli0b2o.css';
import '../../css/f/fr0jglbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s9kli0b2o"/><path class="fr0jglbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:storage-heater-20" /></template>
