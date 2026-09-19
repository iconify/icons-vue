<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilq4mj0ny.css';
import '../../css/a/agps2ol2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilq4mj0ny"/><path class="agps2ol2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:text-to-speech" /></template>
