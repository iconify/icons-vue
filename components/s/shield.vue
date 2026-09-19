<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6-p4wl9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6-p4wl9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:shield" /></template>
