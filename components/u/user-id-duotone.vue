<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svkmrqn0y.css';
import '../../css/k/kybo6ib7m.css';
import '../../css/g/gbl_k3bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svkmrqn0y"/><path class="kybo6ib7m"/><path class="gbl_k3bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-id-duotone" /></template>
