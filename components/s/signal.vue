<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjbugb6if.css';
import '../../css/b/bnu8qk5ih.css';
import '../../css/m/m9byb9ete.css';
import '../../css/m/mmx6ymgpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="cjbugb6if"/><path class="bnu8qk5ih"/><path class="m9byb9ete"/><path class="mmx6ymgpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:signal" /></template>
