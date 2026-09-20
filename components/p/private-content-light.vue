<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2v4it5to.css';
import '../../css/v/velavw33g.css';
import '../../css/k/krzgvzbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2v4it5to"/><path class="velavw33g"/><path class="krzgvzbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:private-content-light" /></template>
