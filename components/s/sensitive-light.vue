<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pplbo7oar.css';
import '../../css/c/c8aj1-b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pplbo7oar"/><path class="c8aj1-b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:sensitive-light" /></template>
