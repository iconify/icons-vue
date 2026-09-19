<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0ndb3slp.css';
import '../../css/v/vpm5wbcdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="j0ndb3slp"/><path class="vpm5wbcdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:okta-wordmark" /></template>
