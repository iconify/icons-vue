<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr7avqm6c.css';
import '../../css/r/rhx6aqb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr7avqm6c"/><path class="rhx6aqb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:question-light" /></template>
