<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxye1ut_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxye1ut_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:stop-fill" /></template>
