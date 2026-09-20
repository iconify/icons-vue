<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x49bj1boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x49bj1boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:phabricator" /></template>
