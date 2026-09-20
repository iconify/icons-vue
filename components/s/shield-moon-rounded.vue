<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-kup55nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-moon-rounded" /></template>
<style>
.q-kup55nm {
  fill: currentColor;
  d: path("M12.525 15.5q.72 0 1.41-.256q.692-.256 1.232-.767q.137-.143.095-.277t-.254-.204q-.931-.285-1.675-.847t-1.25-1.449q-.481-.836-.665-1.782t.167-1.837q.08-.212-.073-.335q-.152-.123-.331-.073q-1.264.44-1.985 1.51q-.721 1.069-.721 2.317q0 1.664 1.184 2.832t2.866 1.168m-.812 5.317q-.15-.025-.28-.075q-2.952-1.125-4.692-3.816T5 11.1V6.817q0-.51.295-.923t.755-.6l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.46.187.755.6t.295.923V11.1q0 3.135-1.74 5.826t-4.693 3.816q-.13.05-.28.075t-.287.025t-.287-.025");
}

</style>
