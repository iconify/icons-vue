<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmv0qjbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nmv0qjbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pydantic-logfire" /></template>
