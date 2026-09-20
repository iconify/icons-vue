<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd8qb6rig.css';
import '../../css/t/tvj-li2ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd8qb6rig"/><path class="tvj-li2ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:vote-yeah-solid" /></template>
