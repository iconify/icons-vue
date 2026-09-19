<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my_fqn8gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my_fqn8gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:social-distancing-not-allowed-space-man" /></template>
