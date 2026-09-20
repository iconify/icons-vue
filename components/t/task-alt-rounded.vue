<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv76nlb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:task-alt-rounded" /></template>
<style>
.nv76nlb9t {
  fill: currentColor;
  d: path("M12 21q-1.864 0-3.506-.71q-1.642-.711-2.857-1.926q-1.216-1.216-1.926-2.858Q3 13.864 3 12t.71-3.506t1.927-2.857T8.494 3.71Q10.137 3 12 3q1.296 0 2.501.362t2.293 1.04q.202.123.267.33q.064.209-.07.385q-.135.177-.355.21t-.409-.09q-.954-.606-2.028-.921T12 4Q8.675 4 6.337 6.338T4 12t2.338 5.663T12 20t5.663-2.337T20 12q0-.373-.032-.734q-.031-.36-.114-.733q-.05-.214.057-.409t.32-.243q.208-.048.375.075t.217.33q.089.408.133.835T21 12q0 1.864-.71 3.506q-.711 1.642-1.926 2.857q-1.216 1.216-2.858 1.926Q13.864 21 12 21m-1.438-6.508l9.377-9.383q.14-.14.34-.152t.367.152q.16.16.16.354t-.16.354l-9.519 9.525q-.243.242-.566.242t-.565-.242l-2.638-2.638q-.14-.14-.15-.345q-.01-.203.15-.363t.354-.16t.354.16z");
}

</style>
