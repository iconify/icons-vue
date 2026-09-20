<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz7cbhboy.css';
import '../../css/j/jww6vuirk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz7cbhboy"/><path class="jww6vuirk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-at-duotone" /></template>
