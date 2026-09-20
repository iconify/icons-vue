<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b59d-rb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b59d-rb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-forms-light" /></template>
