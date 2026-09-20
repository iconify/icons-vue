<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jikk7dwxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:task-alt" /></template>
<style>
.jikk7dwxd {
  fill: currentColor;
  d: path("M12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2q1.625 0 3.075.475T17.75 3.8L16.3 5.275q-.95-.6-2.025-.937T12 4Q8.675 4 6.337 6.338T4 12t2.338 5.663T12 20t5.663-2.337T20 12q0-.45-.05-.9t-.15-.875L21.425 8.6q.275.8.425 1.65T22 12q0 2.075-.788 3.9t-2.137 3.175t-3.175 2.138T12 22m-1.4-5.4l-4.25-4.25l1.4-1.4l2.85 2.85l10-10.025l1.4 1.4z");
}

</style>
