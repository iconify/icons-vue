<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-w1zuldo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:security-rounded" /></template>
<style>
.b-w1zuldo {
  fill: currentColor;
  d: path("M12 19.9q2.425-.75 4.05-2.962T17.95 12H12V4.144L6.404 6.221q-.193.077-.298.231Q6 6.606 6 6.798v4.733q0 .194.05.469H12zm-.287.917q-.15-.025-.28-.075q-2.952-1.125-4.692-3.816T5 11.1V6.817q0-.51.295-.923t.755-.6l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.46.187.755.6t.295.923V11.1q0 3.135-1.74 5.826t-4.693 3.816q-.13.05-.28.075t-.287.025t-.287-.025");
}

</style>
