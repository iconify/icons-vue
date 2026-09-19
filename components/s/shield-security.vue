<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajpwv5bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajpwv5bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:shield-security" /></template>
