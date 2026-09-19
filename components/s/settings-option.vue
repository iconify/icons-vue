<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s63jr007d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s63jr007d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:settings-option" /></template>
