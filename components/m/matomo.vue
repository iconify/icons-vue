<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh9m9zbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh9m9zbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:matomo" /></template>
