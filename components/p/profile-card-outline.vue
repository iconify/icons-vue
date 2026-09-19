<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp_741pqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp_741pqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:profile-card-outline" /></template>
