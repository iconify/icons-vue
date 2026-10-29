<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brfeasb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brfeasb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:sigma" /></template>
