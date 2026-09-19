<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_s2y9nsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_s2y9nsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:mandriva" /></template>
