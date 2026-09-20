<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5gqbfv1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x5gqbfv1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:posthog-light" /></template>
