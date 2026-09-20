<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9vb0jbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9vb0jbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:social-skype" /></template>
