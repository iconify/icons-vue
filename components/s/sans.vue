<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk6sqrv7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk6sqrv7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:sans" /></template>
