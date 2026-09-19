<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg3fc5b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg3fc5b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:waypoint" /></template>
